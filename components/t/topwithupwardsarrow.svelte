<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkn5tq8xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkn5tq8xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:topwithupwardsarrow" {...props}></Icon>
