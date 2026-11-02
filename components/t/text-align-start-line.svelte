<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv745tbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv745tbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-align-start-line" {...props}></Icon>
