<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqvq0wb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvq0wb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-bag-solid" {...props}></Icon>
