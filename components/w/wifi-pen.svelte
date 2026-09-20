<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl69o2b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl69o2b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-pen" {...props}></Icon>
