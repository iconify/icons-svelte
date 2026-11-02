<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3_secbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3_secbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:router-modem-line" {...props}></Icon>
