<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvzlr703x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvzlr703x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sale-outline" {...props}></Icon>
