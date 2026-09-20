<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmzbrk_2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmzbrk_2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:route-square-2" {...props}></Icon>
