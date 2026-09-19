<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwj78c8sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fwj78c8sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vala" {...props}></Icon>
