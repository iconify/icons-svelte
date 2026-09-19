<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tluqhzo9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tluqhzo9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:youtube" {...props}></Icon>
