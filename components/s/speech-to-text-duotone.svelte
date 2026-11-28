<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j76u6_b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j76u6_b3z primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speech-to-text-duotone" {...props}></Icon>
