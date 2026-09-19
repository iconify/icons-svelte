<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0u-p9smw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="t0u-p9smw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:suitcase-rolling" {...props}></Icon>
