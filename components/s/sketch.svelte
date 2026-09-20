<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhnbz4jqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhnbz4jqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sketch" {...props}></Icon>
