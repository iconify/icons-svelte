<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmxa-c6qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmxa-c6qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-terminal-solid" {...props}></Icon>
