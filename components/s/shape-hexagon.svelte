<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlztt-bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlztt-bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:shape-hexagon" {...props}></Icon>
