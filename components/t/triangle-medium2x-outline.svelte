<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up0ti3bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="up0ti3bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-medium2x-outline" {...props}></Icon>
