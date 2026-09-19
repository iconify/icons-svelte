<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxp1t4b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vxp1t4b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:workspace-import" {...props}></Icon>
