<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkwop1f3g.css';
import '../../css/r/romiv8ccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkwop1f3g"/><path class="romiv8ccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-left-up-bold-duotone" {...props}></Icon>
