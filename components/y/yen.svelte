<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfh81vbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="cfh81vbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:yen" {...props}></Icon>
