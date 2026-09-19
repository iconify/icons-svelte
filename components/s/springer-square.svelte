<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa_y83bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wa_y83bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:springer-square" {...props}></Icon>
