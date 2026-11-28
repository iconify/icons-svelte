<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swn1u1bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swn1u1bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shrink" {...props}></Icon>
