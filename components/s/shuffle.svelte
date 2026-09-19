<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qs6hszyma.css';
import '../../css/b/b8nviyb0p.css';
import '../../css/o/osuz1epzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs6hszyma"/><path class="b8nviyb0p"/><path class="osuz1epzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shuffle" {...props}></Icon>
