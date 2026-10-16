<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1vduib2t.css';
import '../../css/h/htcxxr-ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n1vduib2t"/><path class="htcxxr-ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warming-stripes-20-bold" {...props}></Icon>
