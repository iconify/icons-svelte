<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rifpvsy3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rifpvsy3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:solidity" {...props}></Icon>
