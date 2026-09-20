<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbtfd1a_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbtfd1a_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unstop" {...props}></Icon>
