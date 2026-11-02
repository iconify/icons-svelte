<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klncv4kwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klncv4kwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toilet-paper-line" {...props}></Icon>
