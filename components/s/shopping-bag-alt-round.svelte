<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpg36i2em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpg36i2em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-alt-round" {...props}></Icon>
