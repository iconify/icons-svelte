<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvsnzr3ef.css';
import '../../css/t/taasc_mln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvsnzr3ef"/><path class="taasc_mln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-in" {...props}></Icon>
