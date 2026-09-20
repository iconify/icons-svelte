<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nis8n537v.css';
import '../../css/g/gz8l-pnrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nis8n537v"/><path class="gz8l-pnrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tobimake" {...props}></Icon>
