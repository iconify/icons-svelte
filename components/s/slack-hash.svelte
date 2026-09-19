<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz9uhbcoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="oz9uhbcoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:slack-hash" {...props}></Icon>
