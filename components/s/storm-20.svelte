<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obfms-brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="obfms-brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storm-20" {...props}></Icon>
