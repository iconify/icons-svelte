<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oov7omrot.css';
import '../../css/a/a7x1lr5rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oov7omrot"/><path class="a7x1lr5rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:state-of-charge-20" {...props}></Icon>
