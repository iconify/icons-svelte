<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-4x9ob7y.css';
import '../../css/t/t47nc4b6q.css';
import '../../css/a/amdspubws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-4x9ob7y"/><path class="t47nc4b6q"/><path class="amdspubws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:van-20-bold" {...props}></Icon>
