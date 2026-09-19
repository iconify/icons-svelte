<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne0v7dbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ne0v7dbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:solana" {...props}></Icon>
