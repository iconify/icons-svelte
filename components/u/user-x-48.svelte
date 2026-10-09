<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdkgyrbga.css';
import '../../css/s/sd_vembah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdkgyrbga"/><path class="sd_vembah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-x-48" {...props}></Icon>
