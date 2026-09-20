<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8rkslb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i8rkslb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:yuan" {...props}></Icon>
