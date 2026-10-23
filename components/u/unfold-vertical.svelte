<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt7jvlb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt7jvlb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:unfold-vertical" {...props}></Icon>
