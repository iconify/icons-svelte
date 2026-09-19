<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vba-dkb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vba-dkb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:water-wave-big" {...props}></Icon>
