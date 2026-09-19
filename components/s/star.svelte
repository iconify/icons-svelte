<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmnqnxbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1600};
const content = `<path class="lmnqnxbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:star" {...props}></Icon>
