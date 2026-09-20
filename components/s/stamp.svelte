<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mglmu62iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mglmu62iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:stamp" {...props}></Icon>
