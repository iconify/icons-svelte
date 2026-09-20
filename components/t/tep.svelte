<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pynayyb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pynayyb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:tep" {...props}></Icon>
