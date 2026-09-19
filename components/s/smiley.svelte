<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-8gtcm1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="y-8gtcm1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:smiley" {...props}></Icon>
