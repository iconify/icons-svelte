<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnl_rbnua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnl_rbnua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:zero" {...props}></Icon>
