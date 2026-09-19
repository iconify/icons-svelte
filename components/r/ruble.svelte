<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp45j8i-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp45j8i-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:ruble" {...props}></Icon>
