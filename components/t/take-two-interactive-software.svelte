<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue9ks4bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9ks4bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:take-two-interactive-software" {...props}></Icon>
