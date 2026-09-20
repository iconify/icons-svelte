<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owo7uxusz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="owo7uxusz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:vector-nodes-7" {...props}></Icon>
