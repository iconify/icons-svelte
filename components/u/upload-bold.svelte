<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8z1_ib5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8z1_ib5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:upload-bold" {...props}></Icon>
