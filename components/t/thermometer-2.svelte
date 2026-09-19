<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_ea2b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1792};
const content = `<path class="c-_ea2b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thermometer-2" {...props}></Icon>
