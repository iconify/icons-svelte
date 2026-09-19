<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_r9qybay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_r9qybay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shield-off-outline" {...props}></Icon>
