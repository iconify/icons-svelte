<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynmazaczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ynmazaczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:rss" {...props}></Icon>
