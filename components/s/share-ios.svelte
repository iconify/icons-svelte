<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5n8ghm7o.css';
import '../../css/w/wq_f_lb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s5n8ghm7o"/><path class="wq_f_lb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:share-ios" {...props}></Icon>
