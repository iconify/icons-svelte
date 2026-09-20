<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybj_cgbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybj_cgbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-x-solid" {...props}></Icon>
