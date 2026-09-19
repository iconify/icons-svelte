<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydg7xpknt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydg7xpknt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-spray" {...props}></Icon>
