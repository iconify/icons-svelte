<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1p-5-ejl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1p-5-ejl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:wrench" {...props}></Icon>
