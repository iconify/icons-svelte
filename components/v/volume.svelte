<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b66jsbpns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="b66jsbpns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:volume" {...props}></Icon>
