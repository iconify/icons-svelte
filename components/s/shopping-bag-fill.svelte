<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw-n8ebic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-n8ebic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-fill" {...props}></Icon>
