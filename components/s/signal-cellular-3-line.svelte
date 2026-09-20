<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5t-u2bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5t-u2bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-cellular-3-line" {...props}></Icon>
