<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-xu_c3ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="u-xu_c3ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sad-cry" {...props}></Icon>
