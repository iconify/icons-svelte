<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykxa_t03c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ykxa_t03c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:windows" {...props}></Icon>
