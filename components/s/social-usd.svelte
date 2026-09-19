<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrabqj9ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrabqj9ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-usd" {...props}></Icon>
