<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuwzd47ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuwzd47ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:share" {...props}></Icon>
