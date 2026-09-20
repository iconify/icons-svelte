<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af4lzgb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="af4lzgb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:triangle-filled-32" {...props}></Icon>
