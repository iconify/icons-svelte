<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7jme086z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7jme086z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shield-minus" {...props}></Icon>
