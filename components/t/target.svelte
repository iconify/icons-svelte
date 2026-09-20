<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij0_li78p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ij0_li78p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:target" {...props}></Icon>
