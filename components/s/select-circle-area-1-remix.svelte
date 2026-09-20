<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5pwa2bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t5pwa2bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:select-circle-area-1-remix" {...props}></Icon>
