<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdz9c9buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vdz9c9buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-pellets-20" {...props}></Icon>
