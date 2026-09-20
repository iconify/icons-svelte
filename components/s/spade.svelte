<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogv-8seqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogv-8seqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spade" {...props}></Icon>
