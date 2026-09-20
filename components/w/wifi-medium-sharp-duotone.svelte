<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/mc8rtl3wh.css';
import '../../css/b/b8uh54bhe.css';
import '../../css/c/chh9m8bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mc8rtl3wh"/><path class="b8uh54bhe"/><path class="chh9m8bfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wifi-medium-sharp-duotone" {...props}></Icon>
