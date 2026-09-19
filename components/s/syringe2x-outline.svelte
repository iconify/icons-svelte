<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1a8b3mdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j1a8b3mdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:syringe2x-outline" {...props}></Icon>
