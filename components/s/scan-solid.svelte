<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icdflt42b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icdflt42b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:scan-solid" {...props}></Icon>
