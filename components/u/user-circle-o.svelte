<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewkexulyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ewkexulyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:user-circle-o" {...props}></Icon>
