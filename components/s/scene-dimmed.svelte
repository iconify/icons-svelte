<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbz_imbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbz_imbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:scene-dimmed" {...props}></Icon>
