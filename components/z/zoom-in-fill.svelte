<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbl-9e6zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbl-9e6zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:zoom-in-fill" {...props}></Icon>
