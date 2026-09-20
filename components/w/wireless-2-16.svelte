<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2sp9xloz.css';
import '../../css/c/cg9on-ftx.css';
import '../../css/s/swaugsbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2sp9xloz"/><path class="cg9on-ftx"/><path class="swaugsbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wireless-2-16" {...props}></Icon>
