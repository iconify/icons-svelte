<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r38q_w2xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1029};
const content = `<path class="r38q_w2xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ubuntu" {...props}></Icon>
