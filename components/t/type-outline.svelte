<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnc440cal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnc440cal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:type-outline" {...props}></Icon>
