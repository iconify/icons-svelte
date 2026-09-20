<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw7kbwzdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw7kbwzdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-line-stacked" {...props}></Icon>
