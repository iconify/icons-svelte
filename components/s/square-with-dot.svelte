<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvh6w0bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cvh6w0bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:square-with-dot" {...props}></Icon>
