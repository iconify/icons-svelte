<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aayrck8cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aayrck8cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vtx" {...props}></Icon>
