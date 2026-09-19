<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syt3s17lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="syt3s17lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:volume-down" {...props}></Icon>
