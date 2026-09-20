<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcujsn75d.css';
import '../../css/a/a3rqikbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcujsn75d"/><path class="a3rqikbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:shft" {...props}></Icon>
