<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htzosabxt.css';
import '../../css/r/rbd0bhbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="htzosabxt"/><path class="rbd0bhbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snorkel" {...props}></Icon>
