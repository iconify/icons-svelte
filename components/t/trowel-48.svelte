<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thafg6bsi.css';
import '../../css/q/qglubxbcs.css';
import '../../css/l/lnfvw2unm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thafg6bsi"/><path class="qglubxbcs"/><path class="lnfvw2unm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trowel-48" {...props}></Icon>
