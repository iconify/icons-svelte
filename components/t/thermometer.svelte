<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glx76xnxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glx76xnxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:thermometer" {...props}></Icon>
