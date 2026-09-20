<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnqqqb4zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnqqqb4zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-up-fill" {...props}></Icon>
