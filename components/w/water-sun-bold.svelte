<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dth18jb_c.css';
import '../../css/b/bx1khacep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dth18jb_c"/><path class="bx1khacep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:water-sun-bold" {...props}></Icon>
