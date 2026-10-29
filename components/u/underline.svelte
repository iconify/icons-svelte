<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obvmtpyhu.css';
import '../../css/t/tqpyvlb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obvmtpyhu wm-k"/><path class="tqpyvlb9z wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:underline" {...props}></Icon>
