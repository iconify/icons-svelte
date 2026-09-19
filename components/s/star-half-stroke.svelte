<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxxgum2ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gxxgum2ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:star-half-stroke" {...props}></Icon>
