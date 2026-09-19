<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brvau-b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brvau-b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:yen" {...props}></Icon>
