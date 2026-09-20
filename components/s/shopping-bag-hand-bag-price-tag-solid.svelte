<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dad1_xhcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dad1_xhcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-bag-hand-bag-price-tag-solid" {...props}></Icon>
