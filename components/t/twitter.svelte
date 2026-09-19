<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fooidy7tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="fooidy7tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:twitter" {...props}></Icon>
