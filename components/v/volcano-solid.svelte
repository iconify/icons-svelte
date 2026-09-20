<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9kxh0b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c9kxh0b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volcano-solid" {...props}></Icon>
