<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsfm-8bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zsfm-8bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:video" {...props}></Icon>
