<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_b44o1vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_b44o1vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trending-up-down" {...props}></Icon>
