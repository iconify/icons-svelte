<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zckaopb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zckaopb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:shuffle-remix" {...props}></Icon>
