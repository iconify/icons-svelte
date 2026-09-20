<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6_q2dyiy.css';
import '../../css/q/q2inojbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6_q2dyiy"/><path class="q2inojbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storybook" {...props}></Icon>
