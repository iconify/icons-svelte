<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr5fm0bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr5fm0bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tape-line" {...props}></Icon>
