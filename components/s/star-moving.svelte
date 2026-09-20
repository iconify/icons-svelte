<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sks34e18g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sks34e18g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:star-moving" {...props}></Icon>
