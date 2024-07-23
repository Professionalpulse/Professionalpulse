- // Generated code for this Row Widget...
Padding(
  padding: EdgeInsetsDirectional.fromSTEB(0, 120, 0, 0),
  child: Row(
    mainAxisSize: MainAxisSize.max,
    children: [
      Padding(
        padding: EdgeInsetsDirectional.fromSTEB(30, 0, 0, 0),
        child: Icon(
          Icons.report_rounded,
          color: Colors.black,
          size: 50,
        ),
      ),
      Padding(
        padding: EdgeInsetsDirectional.fromSTEB(59, 0, 0, 0),
        child: InkWell(
          splashColor: Colors.transparent,
          focusColor: Colors.transparent,
          hoverColor: Colors.transparent,
          highlightColor: Colors.transparent,
          onTap: () async {
            context.pushNamed('subpage');
          },
          child: Icon(
            Icons.person_rounded,
            color: Colors.black,
            size: 50,
          ),
        ),
      ),
      Padding(
        padding: EdgeInsetsDirectional.fromSTEB(67, 0, 0, 0),
        child: InkWell(
          splashColor: Colors.transparent,
          focusColor: Colors.transparent,
          hoverColor: Colors.transparent,
          highlightColor: Colors.transparent,
          onTap: () async {
            context.pushNamed('textpage');
          },
          child: Icon(
            Icons.text_fields,
            color: Colors.black,
            size: 50,
          ),
        ),
      ),
      Padding(
        padding: EdgeInsetsDirectional.fromSTEB(50, 0, 0, 2),
        child: Icon(
          Icons.block_rounded,
          color: Colors.black,
          size: 50,
        ),
      ),
    ],
  ),
)
