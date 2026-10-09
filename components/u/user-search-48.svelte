<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6otzvulu.css';
import '../../css/g/gczovap1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h6otzvulu"/><path class="gczovap1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-search-48" {...props}></Icon>
