<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwbi4p-v.css';
import '../../css/f/f_y7kz9fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vlwbi4p-v"/><path class="f_y7kz9fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-low-20" {...props}></Icon>
