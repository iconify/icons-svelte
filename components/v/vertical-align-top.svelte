<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nql2phbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nql2phbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:vertical-align-top" {...props}></Icon>
