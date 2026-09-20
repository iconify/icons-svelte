<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q975aab4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q975aab4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-line" {...props}></Icon>
