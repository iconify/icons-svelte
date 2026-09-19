<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thk5s-brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="thk5s-brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:spacex" {...props}></Icon>
