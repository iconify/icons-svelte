<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5-lonbvr.css';
import '../../css/c/cs_yflpck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5-lonbvr"/><path clip-rule="evenodd" class="cs_yflpck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:turborepo" {...props}></Icon>
