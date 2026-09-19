<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdv_lbcih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdv_lbcih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:three-three" {...props}></Icon>
