<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5504zl5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5504zl5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-2-line" {...props}></Icon>
