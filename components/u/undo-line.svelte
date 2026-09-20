<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shdx1tgjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shdx1tgjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:undo-line" {...props}></Icon>
