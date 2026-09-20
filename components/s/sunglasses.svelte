<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fziy_koug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fziy_koug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sunglasses" {...props}></Icon>
