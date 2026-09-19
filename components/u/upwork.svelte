<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnr3bz6_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dnr3bz6_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:upwork" {...props}></Icon>
