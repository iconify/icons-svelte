<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5exjcboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5exjcboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:screen-share" {...props}></Icon>
