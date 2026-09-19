<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8advlwls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b f8advlwls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:size-distort" {...props}></Icon>
