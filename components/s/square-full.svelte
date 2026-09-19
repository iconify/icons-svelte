<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9jgx7bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9jgx7bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-full" {...props}></Icon>
