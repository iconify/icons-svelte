<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la79i3b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la79i3b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:test-tube-line" {...props}></Icon>
