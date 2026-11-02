<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/roevd8b-x.css';
import '../../css/s/spj1chbgp.css';
import '../../css/r/ra2quftzu.css';
import '../../css/j/j_hxbbc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="roevd8b-x"/><path class="spj1chbgp"/><path class="ra2quftzu"/><path class="j_hxbbc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:telescope" {...props}></Icon>
