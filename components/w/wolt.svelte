<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_8xh-nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":154,"height":56};
const content = `<path class="ec_8xh-nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wolt" {...props}></Icon>
