<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxid2bbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kxid2bbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sofa" {...props}></Icon>
