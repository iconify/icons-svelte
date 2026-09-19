<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu3xopu2a.css';
import '../../css/k/kbs2nvbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu3xopu2a"/><path class="kbs2nvbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:washer" {...props}></Icon>
