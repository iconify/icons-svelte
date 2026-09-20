<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3epa78jl.css';
import '../../css/b/b11srpowt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3epa78jl"/><path class="b11srpowt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:town-filled" {...props}></Icon>
