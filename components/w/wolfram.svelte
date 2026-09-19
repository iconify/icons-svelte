<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lip3he57t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lip3he57t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wolfram" {...props}></Icon>
