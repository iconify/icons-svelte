<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnb-2sb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cnb-2sb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:tagcloud" {...props}></Icon>
