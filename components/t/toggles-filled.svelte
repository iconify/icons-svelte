<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y75ybwfrp.css';
import '../../css/w/wmxza4_8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y75ybwfrp"/><path class="wmxza4_8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggles-filled" {...props}></Icon>
