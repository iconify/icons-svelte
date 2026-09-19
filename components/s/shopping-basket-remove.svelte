<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bic_6imzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="bic_6imzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-basket-remove" {...props}></Icon>
