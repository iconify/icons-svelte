<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb7iy8b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb7iy8b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-medium" {...props}></Icon>
