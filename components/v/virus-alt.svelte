<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voq30zbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="voq30zbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-alt" {...props}></Icon>
