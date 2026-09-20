<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbzck1ymf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbzck1ymf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wrench-solid" {...props}></Icon>
