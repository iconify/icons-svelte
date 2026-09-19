<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/und8i-7ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="und8i-7ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-outdated-stroke-12" {...props}></Icon>
