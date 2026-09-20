<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-xy7fdst.css';
import '../../css/h/hcnon4f5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-xy7fdst"/><path class="hcnon4f5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:swash" {...props}></Icon>
