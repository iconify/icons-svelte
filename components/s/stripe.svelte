<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drjns0whf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drjns0whf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:stripe" {...props}></Icon>
