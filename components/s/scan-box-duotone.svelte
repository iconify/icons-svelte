<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4b3--kmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4b3--kmd primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-box-duotone" {...props}></Icon>
