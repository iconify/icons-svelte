<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_llad4ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g_llad4ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sd-card" {...props}></Icon>
