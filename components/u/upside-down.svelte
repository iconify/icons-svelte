<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pju9q-5bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pju9q-5bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:upside-down" {...props}></Icon>
