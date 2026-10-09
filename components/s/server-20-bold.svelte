<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oypv3gvwf.css';
import '../../css/i/iv7ikabdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oypv3gvwf"/><path class="iv7ikabdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-20-bold" {...props}></Icon>
