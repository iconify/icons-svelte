<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w90ht-b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w90ht-b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-shield-line" {...props}></Icon>
