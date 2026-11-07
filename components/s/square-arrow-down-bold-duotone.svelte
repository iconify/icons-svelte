<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftxh2yu-e.css';
import '../../css/e/esz28i62g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftxh2yu-e"/><path class="esz28i62g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-down-bold-duotone" {...props}></Icon>
