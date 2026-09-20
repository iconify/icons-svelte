<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bxr8mzbxm.css';
import '../../css/z/zvnq6zy0d.css';
import '../../css/f/fhnye3b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bxr8mzbxm"/><path class="zvnq6zy0d"/><path class="fhnye3b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-ring-broken" {...props}></Icon>
