<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubfgqsalz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":193.3};
const content = `<path class="ubfgqsalz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zte" {...props}></Icon>
