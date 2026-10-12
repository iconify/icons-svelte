<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfcc4qbni.css';
import '../../css/y/ym-zwb07i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcc4qbni"/><path class="ym-zwb07i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-cart-plus-filled" {...props}></Icon>
