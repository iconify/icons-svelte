<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brv3fxbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="brv3fxbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tachograph-digital" {...props}></Icon>
