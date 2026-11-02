<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5_b0h3gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5_b0h3gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sound-line-fill" {...props}></Icon>
