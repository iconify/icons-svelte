<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa6bskkcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="qa6bskkcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tv" {...props}></Icon>
