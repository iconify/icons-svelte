<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzdbeubvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzdbeubvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scooter-line" {...props}></Icon>
