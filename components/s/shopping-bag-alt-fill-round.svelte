<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcu2-ibcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcu2-ibcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-alt-fill-round" {...props}></Icon>
