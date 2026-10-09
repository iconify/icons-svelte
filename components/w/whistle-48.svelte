<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pek7vnbxc.css';
import '../../css/y/ywj7khc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pek7vnbxc"/><path class="ywj7khc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whistle-48" {...props}></Icon>
