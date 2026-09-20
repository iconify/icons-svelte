<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4_m0unth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4_m0unth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-actions-edit-2-bold" {...props}></Icon>
