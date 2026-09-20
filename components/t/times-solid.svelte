<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf63asb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf63asb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times-solid" {...props}></Icon>
