<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_z88zi0a.css';
import '../../css/g/ga3uofb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z_z88zi0a"/><path class="ga3uofb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-check-48-bold" {...props}></Icon>
