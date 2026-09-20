<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5o9yeae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":250,"height":62.734};
const content = `<path class="vc5o9yeae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uchicago" {...props}></Icon>
