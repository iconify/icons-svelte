<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6pws_bay.css';
import '../../css/x/xj2ftdbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c6pws_bay"/><path clip-rule="evenodd" class="xj2ftdbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:vector-document-solid" {...props}></Icon>
