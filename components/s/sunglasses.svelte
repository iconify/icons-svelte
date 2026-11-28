<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzty5h1lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzty5h1lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sunglasses" {...props}></Icon>
