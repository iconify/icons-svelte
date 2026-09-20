<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2fosdizo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2fosdizo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-sad-1-bold" {...props}></Icon>
