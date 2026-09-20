<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh00q-bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bh00q-bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:waku" {...props}></Icon>
