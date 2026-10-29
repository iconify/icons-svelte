<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw78_1bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw78_1bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:weight-solid" {...props}></Icon>
