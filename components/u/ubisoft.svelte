<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a98m-pyyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a98m-pyyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ubisoft" {...props}></Icon>
