<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5_f4-b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5_f4-b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:thermometer-sun-solid" {...props}></Icon>
