<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlsc8mb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlsc8mb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-round" {...props}></Icon>
