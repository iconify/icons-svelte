<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_l0pbn1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_l0pbn1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:solo" {...props}></Icon>
