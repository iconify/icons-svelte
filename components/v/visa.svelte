<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ule2qfbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ule2qfbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:visa" {...props}></Icon>
