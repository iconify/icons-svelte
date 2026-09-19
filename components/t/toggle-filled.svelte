<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6-x6hoxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m6-x6hoxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:toggle-filled" {...props}></Icon>
