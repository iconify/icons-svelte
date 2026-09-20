<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oss2782tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oss2782tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-settings" {...props}></Icon>
