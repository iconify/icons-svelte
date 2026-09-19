<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0oxfv-jn.css';
import '../../css/y/yf-k82b-b.css';
import '../../css/k/krcvqcb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="o0oxfv-jn"/><circle class="yf-k82b-b"/><path class="krcvqcb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:support-vector-machine" {...props}></Icon>
