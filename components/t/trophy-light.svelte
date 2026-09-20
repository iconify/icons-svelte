<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq532vbvh.css';
import '../../css/r/r-nejf7ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq532vbvh"/><path class="r-nejf7ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trophy-light" {...props}></Icon>
