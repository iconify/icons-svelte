<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_vc3bc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q_vc3bc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-half-20" {...props}></Icon>
