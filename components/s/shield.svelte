<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdp7e5d1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdp7e5d1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:shield" {...props}></Icon>
