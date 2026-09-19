<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3-m1jbcu.css';
import '../../css/q/q45ggwbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3-m1jbcu"/><path class="q45ggwbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shopping-bags" {...props}></Icon>
