<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo4uwlb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1536};
const content = `<path class="wo4uwlb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:unlock-alt" {...props}></Icon>
