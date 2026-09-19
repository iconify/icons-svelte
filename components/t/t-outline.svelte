<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4zp6bl0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i4zp6bl0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:t-outline" {...props}></Icon>
