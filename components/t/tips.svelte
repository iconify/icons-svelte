<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b22cvxy9q.css';
import '../../css/s/sea5vybym.css';
import '../../css/r/raype-70g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b22cvxy9q"/><path class="sea5vybym"/><path class="raype-70g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tips" {...props}></Icon>
