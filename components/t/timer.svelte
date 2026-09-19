<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqgyjgqnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqgyjgqnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:timer" {...props}></Icon>
