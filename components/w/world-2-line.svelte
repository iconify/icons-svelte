<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz3fe2bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3fe2bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-2-line" {...props}></Icon>
