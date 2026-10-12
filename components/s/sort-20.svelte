<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4shs0_ov.css';
import '../../css/t/t8d9w-tva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i4shs0_ov"/><path class="t8d9w-tva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-20" {...props}></Icon>
