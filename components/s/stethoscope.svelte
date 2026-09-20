<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo5ibeb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wo5ibeb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stethoscope" {...props}></Icon>
