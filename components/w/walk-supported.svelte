<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqf_wfdiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pqf_wfdiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:walk-supported" {...props}></Icon>
