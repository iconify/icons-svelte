<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm_yu0bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm_yu0bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:showtime" {...props}></Icon>
