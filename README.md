# Blender 4.1 IK Rig SKM_Manny para criar animações na Unreal Engine 5
Esse é um projeto feito no blender, nele você pode encontrar o personagem SKM_Manny, com um sistema de IK completo para que consiga criar animações compativeis com o modelo padrão de rig da Unreal Engine 5.

# Como criar as animações?
1. Ao abrir o arquivo no blender selecione o rig de animação e de exportação e entre no modo de edição de poses.
2. Deste modo poderá criar os frames da animação do personagem no editor de animações.
3. Salve a posição, rotação e escala dos ossos, recomendo que faça isso também para os ossos do rig de contendo a cinemática inversa, isso irá facilitar seu trabalho.
4. Após terminar a animação, saia do modo de edição de animações e selecione os objetos da collection nomeada "export" e exporte o rig em formato FBX com as configurações padrão para a UE5, isso é muito simples e existem vários vídeos no youtube sobre o tema (Recomendo apenas exportar o "Armature", as animações não precisam de mesh na UE5 e neste caso o personagem é o modelo padrão da UE5).
5. Após isso importe o ".FBX" na UE5, e não esqueça de selecionar o modelo de ossos "SK_Mannequin" como skeleton.
