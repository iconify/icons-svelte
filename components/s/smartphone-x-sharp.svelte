<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_hs7szqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hs7szqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-x-sharp" {...props}></Icon>
