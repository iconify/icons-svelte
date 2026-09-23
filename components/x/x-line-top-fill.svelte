<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1y_t4b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1y_t4b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:x-line-top-fill" {...props}></Icon>
