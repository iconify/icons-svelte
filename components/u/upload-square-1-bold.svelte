<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh21a-bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh21a-bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:upload-square-1-bold" {...props}></Icon>
