<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-ii4f7on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ii4f7on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:train-track" {...props}></Icon>
