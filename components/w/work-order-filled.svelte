<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvajadb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kvajadb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-filled" {...props}></Icon>
