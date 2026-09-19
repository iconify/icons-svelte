<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oufnes2zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oufnes2zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:work" {...props}></Icon>
