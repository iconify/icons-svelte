<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq5y7ybkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq5y7ybkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sos" {...props}></Icon>
