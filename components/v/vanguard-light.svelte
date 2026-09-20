<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x39p64gnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x39p64gnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vanguard-light" {...props}></Icon>
