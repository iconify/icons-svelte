<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydl-c6bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydl-c6bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:uml" {...props}></Icon>
