<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltw3g9bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltw3g9bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scan-traces" {...props}></Icon>
