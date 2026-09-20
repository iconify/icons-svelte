<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbb7tzb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbb7tzb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:snowflake" {...props}></Icon>
