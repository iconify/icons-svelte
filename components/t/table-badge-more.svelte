<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiul_cbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qiul_cbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:table-badge-more" {...props}></Icon>
