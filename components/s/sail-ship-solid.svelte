<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izs_rbb_s.css';
import '../../css/p/pt6hrq4xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="izs_rbb_s"/><path class="pt6hrq4xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sail-ship-solid" {...props}></Icon>
