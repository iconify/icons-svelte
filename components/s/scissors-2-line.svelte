<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seqw72ltl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seqw72ltl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scissors-2-line" {...props}></Icon>
