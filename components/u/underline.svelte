<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1tsdfg2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1tsdfg2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:underline" {...props}></Icon>
