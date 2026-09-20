<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrndijm8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lrndijm8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wall" {...props}></Icon>
