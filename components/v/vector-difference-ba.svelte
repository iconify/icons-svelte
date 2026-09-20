<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5tkjobrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5tkjobrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-difference-ba" {...props}></Icon>
