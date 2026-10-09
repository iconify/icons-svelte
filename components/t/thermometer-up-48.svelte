<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxju_n3um.css';
import '../../css/t/tyo480b-b.css';
import '../../css/o/o-4655baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nxju_n3um"/><path class="tyo480b-b"/><path class="o-4655baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-up-48" {...props}></Icon>
