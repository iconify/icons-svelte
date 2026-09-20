<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p73b5vb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p73b5vb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tumblr" {...props}></Icon>
