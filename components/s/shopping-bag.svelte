<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acc2ezl_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="acc2ezl_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag" {...props}></Icon>
