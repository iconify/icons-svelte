<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz_y9zzsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_y9zzsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wrench-sharp" {...props}></Icon>
