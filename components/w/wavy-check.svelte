<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8fdwb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp8fdwb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:wavy-check" {...props}></Icon>
