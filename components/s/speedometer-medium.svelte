<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhvp3reay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvp3reay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speedometer-medium" {...props}></Icon>
