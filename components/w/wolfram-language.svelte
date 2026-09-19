<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkzpn6n4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dkzpn6n4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wolfram-language" {...props}></Icon>
