<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j1nmznbff.css';
import '../../css/d/dyy63hbaz.css';
import '../../css/y/y3q2v7bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j1nmznbff"/><path class="dyy63hbaz"/><path class="y3q2v7bge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rings-outline" {...props}></Icon>
