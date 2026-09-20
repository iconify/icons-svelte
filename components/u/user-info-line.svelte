<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnhf1jtvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnhf1jtvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-info-line" {...props}></Icon>
