<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzfb953yw.css';
import '../../css/n/n112oparr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dzfb953yw"/><path class="n112oparr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:screen-arrow-up-stroke-20" {...props}></Icon>
