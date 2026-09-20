<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevmlbz-z.css';
import '../../css/s/swaugsbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uevmlbz-z"/><path class="swaugsbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wireless-1-16" {...props}></Icon>
