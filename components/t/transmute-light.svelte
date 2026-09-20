<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5-xe2bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n5-xe2bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:transmute-light" {...props}></Icon>
