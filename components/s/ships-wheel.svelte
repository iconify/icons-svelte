<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdkr5jbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wdkr5jbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ships-wheel" {...props}></Icon>
