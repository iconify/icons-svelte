<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esz_ho-hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="esz_ho-hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:village-buildings" {...props}></Icon>
