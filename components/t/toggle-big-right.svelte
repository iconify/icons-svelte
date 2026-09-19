<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvnle8ghx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvnle8ghx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggle-big-right" {...props}></Icon>
