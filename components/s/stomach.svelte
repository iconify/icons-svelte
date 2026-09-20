<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4yrdmeaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t4yrdmeaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stomach" {...props}></Icon>
