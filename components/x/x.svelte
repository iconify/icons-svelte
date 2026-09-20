<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsuub8p2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsuub8p2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:x" {...props}></Icon>
