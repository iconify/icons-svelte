<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2sqt4boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d2sqt4boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ruler-remix" {...props}></Icon>
