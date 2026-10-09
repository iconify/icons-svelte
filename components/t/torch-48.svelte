<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf57_hl-a.css';
import '../../css/q/qrxusubxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cf57_hl-a"/><path class="qrxusubxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:torch-48" {...props}></Icon>
