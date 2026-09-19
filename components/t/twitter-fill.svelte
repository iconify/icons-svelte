<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msd0nxxnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msd0nxxnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:twitter-fill" {...props}></Icon>
