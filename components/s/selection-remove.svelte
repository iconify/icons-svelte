<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl0-88b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl0-88b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-remove" {...props}></Icon>
