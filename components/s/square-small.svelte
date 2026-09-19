<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw_kycnzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sw_kycnzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:square-small" {...props}></Icon>
