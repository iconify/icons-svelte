<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iipx-2axi.css';
import '../../css/w/wb8zavuhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iipx-2axi"/><path clip-rule="evenodd" class="wb8zavuhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ui-panel-bottom-16" {...props}></Icon>
