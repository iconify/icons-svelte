<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7u_32bvh.css';
import '../../css/x/x39yvob4g.css';
import '../../css/l/l105bfj4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGr77DHd6N" class="e7u_32bvh"/></defs><use href="#SVGr77DHd6N" class="x39yvob4g"/><use href="#SVGr77DHd6N" class="x39yvob4g"/><path class="l105bfj4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-duotone" {...props}></Icon>
