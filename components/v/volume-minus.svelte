<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj-cleflh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="gj-cleflh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-minus" {...props}></Icon>
