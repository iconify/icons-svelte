<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/j/j5rbj8b1h.css';
import '../../css/h/hljce7egt.css';
import '../../css/x/xwal0ybbu.css';
import '../../css/y/y8o8afbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="j5rbj8b1h wm-shadow"/><path class="hljce7egt wm-shadow"/><path class="xwal0ybbu"/><path class="y8o8afbbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:split" {...props}></Icon>
