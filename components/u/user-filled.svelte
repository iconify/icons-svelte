<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uche6nifg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uche6nifg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:user-filled" {...props}></Icon>
