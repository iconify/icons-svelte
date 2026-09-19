<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw34l_k7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fw34l_k7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ruble" {...props}></Icon>
