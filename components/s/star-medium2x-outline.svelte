<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rthdijk0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rthdijk0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:star-medium2x-outline" {...props}></Icon>
