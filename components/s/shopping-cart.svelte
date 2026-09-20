<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs7ndvbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs7ndvbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:shopping-cart" {...props}></Icon>
