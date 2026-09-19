<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn0goxnbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn0goxnbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:unavailable-light" {...props}></Icon>
