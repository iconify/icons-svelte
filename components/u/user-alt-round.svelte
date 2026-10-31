<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiz9_bcjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiz9_bcjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-alt-round" {...props}></Icon>
