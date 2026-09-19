<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuwt53rzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uuwt53rzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:syringe" {...props}></Icon>
