<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4ekznb-a.css';
import '../../css/u/ucfqbabvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ekznb-a"/><path class="ucfqbabvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-bold-duotone" {...props}></Icon>
