<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frzcg76an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="frzcg76an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:x" {...props}></Icon>
