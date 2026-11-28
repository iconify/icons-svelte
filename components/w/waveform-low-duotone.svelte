<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8d70voog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8d70voog primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-low-duotone" {...props}></Icon>
