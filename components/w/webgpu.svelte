<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoz629bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoz629bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webgpu" {...props}></Icon>
