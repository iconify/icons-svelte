<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzlqtc6qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlqtc6qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:voice-scan" {...props}></Icon>
