<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfomj3bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xfomj3bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:webcomponents-org" {...props}></Icon>
