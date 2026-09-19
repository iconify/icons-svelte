<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlivm3flo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hlivm3flo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tampermonkey" {...props}></Icon>
