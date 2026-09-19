<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vat5sxy9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vat5sxy9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sourceforge" {...props}></Icon>
