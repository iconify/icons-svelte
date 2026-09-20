<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtc8-gbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtc8-gbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-half-full" {...props}></Icon>
