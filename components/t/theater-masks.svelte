<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2hq8bblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g2hq8bblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:theater-masks" {...props}></Icon>
