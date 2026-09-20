<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8scinpfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o8scinpfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-like-outline" {...props}></Icon>
