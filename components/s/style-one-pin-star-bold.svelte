<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmr60dzfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmr60dzfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:style-one-pin-star-bold" {...props}></Icon>
