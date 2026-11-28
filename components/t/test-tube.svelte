<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3--07bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3--07bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:test-tube" {...props}></Icon>
