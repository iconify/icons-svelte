<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imgoe2enx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imgoe2enx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:triangle-right" {...props}></Icon>
