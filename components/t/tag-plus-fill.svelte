<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icuux6bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icuux6bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tag-plus-fill" {...props}></Icon>
