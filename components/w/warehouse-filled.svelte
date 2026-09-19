<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl2o4cc0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl2o4cc0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:warehouse-filled" {...props}></Icon>
