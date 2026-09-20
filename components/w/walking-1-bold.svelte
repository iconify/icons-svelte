<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiq9r0b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiq9r0b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:walking-1-bold" {...props}></Icon>
