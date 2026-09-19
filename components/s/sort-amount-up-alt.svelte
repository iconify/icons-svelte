<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpewheg8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kpewheg8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-amount-up-alt" {...props}></Icon>
