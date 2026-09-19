<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6-b3tbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6-b3tbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:slack" {...props}></Icon>
