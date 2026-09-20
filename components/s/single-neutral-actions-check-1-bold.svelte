<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc0uu2uxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc0uu2uxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-actions-check-1-bold" {...props}></Icon>
