<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfrh74bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfrh74bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-face-solid" {...props}></Icon>
