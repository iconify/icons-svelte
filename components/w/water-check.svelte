<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh6dfm5rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh6dfm5rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-check" {...props}></Icon>
