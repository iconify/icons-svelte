<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mit9zdbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mit9zdbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shopping-basket" {...props}></Icon>
