<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1kfk_bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k1kfk_bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:squared-minus" {...props}></Icon>
