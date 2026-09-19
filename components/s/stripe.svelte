<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6le-k8fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g6le-k8fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:stripe" {...props}></Icon>
