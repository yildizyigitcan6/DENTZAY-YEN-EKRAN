##YENİ EKRAN
<img width="238" height="555" alt="Screenshot_105" src="https://github.com/user-attachments/assets/c2334e8b-ddea-49b4-88dc-db60e3043e34" />

#Widget Code
class Estoque extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Column(
      children: [
        Container(
          width: 375,
          height: 883,
          clipBehavior: Clip.antiAlias,
          decoration: ShapeDecoration(
            color: const Color(0xFFF9FBFF),
            shape: RoundedRectangleBorder(
              borderRadius: BorderRadius.circular(35),
            ),
          ),
          child: Stack(
            children: [
              Positioned(
                left: 16,
                top: 663.48,
                child: Container(
                  width: 164,
                  height: 76.52,
                  decoration: ShapeDecoration(
                    color: Colors.white,
