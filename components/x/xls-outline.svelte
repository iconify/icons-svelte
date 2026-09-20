<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t55u-kbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t55u-kbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:xls-outline" {...props}></Icon>
