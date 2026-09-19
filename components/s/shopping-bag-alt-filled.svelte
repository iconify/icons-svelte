<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfs57crqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfs57crqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shopping-bag-alt-filled" {...props}></Icon>
