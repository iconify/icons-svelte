<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn7-o7nhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dn7-o7nhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:timer" {...props}></Icon>
