<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neqi2zbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="neqi2zbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:rupee" {...props}></Icon>
