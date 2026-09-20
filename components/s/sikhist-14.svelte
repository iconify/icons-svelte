<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yag0wmb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yag0wmb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:sikhist-14" {...props}></Icon>
