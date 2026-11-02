<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo2s3r1kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo2s3r1kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sleigh-line" {...props}></Icon>
