<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvjckikhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nvjckikhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-face-id-mask" {...props}></Icon>
