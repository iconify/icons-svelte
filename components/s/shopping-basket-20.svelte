<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_cl9xend.css';
import '../../css/t/toul2psij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v_cl9xend"/><path class="toul2psij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-basket-20" {...props}></Icon>
