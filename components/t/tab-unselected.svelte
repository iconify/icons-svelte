<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvdcov6gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="nvdcov6gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tab-unselected" {...props}></Icon>
