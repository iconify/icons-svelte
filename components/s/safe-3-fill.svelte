<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzzgo7biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzzgo7biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safe-3-fill" {...props}></Icon>
