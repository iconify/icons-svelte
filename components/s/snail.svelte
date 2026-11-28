<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3xfm5bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3xfm5bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:snail" {...props}></Icon>
