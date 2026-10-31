<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phhi86ilx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phhi86ilx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-round" {...props}></Icon>
