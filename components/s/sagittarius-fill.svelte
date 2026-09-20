<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ssei76h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ssei76h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sagittarius-fill" {...props}></Icon>
