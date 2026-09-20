<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsl9_-rus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rsl9_-rus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wrap-arc-upper" {...props}></Icon>
