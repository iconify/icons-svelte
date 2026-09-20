<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-lkn43o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qq-lkn43o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:voice-scan-1-remix" {...props}></Icon>
