<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm6_lzbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fm6_lzbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:truck" {...props}></Icon>
