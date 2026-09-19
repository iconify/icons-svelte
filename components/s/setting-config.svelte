<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrclusb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nrclusb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:setting-config" {...props}></Icon>
