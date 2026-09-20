<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrnc2rbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rrnc2rbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:skull-2-remix" {...props}></Icon>
