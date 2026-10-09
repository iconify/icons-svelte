<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc18sub8n.css';
import '../../css/i/iuqdpw_hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gc18sub8n"/><path class="iuqdpw_hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-20" {...props}></Icon>
