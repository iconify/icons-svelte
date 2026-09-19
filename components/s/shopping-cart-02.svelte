<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svy-d9glg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svy-d9glg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:shopping-cart-02" {...props}></Icon>
