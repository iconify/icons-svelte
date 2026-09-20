<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvfgu0lvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tvfgu0lvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon" {...props}></Icon>
