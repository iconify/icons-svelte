<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3hmm8bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l3hmm8bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:signature-ltr" {...props}></Icon>
