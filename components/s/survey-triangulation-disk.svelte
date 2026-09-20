<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6o2llfuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6o2llfuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:survey-triangulation-disk" {...props}></Icon>
