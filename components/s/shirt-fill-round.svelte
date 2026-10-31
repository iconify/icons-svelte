<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-d-hbipu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-d-hbipu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shirt-fill-round" {...props}></Icon>
