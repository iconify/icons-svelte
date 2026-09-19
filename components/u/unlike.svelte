<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tssr405-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tssr405-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:unlike" {...props}></Icon>
