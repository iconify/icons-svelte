<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4cxyabxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4cxyabxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:story-post" {...props}></Icon>
