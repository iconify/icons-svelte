<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdd_c94rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pdd_c94rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:search-visual-solid" {...props}></Icon>
