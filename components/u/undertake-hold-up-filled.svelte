<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sde3gc6on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sde3gc6on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:undertake-hold-up-filled" {...props}></Icon>
