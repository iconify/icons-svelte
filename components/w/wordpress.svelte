<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm4461bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hm4461bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wordpress" {...props}></Icon>
