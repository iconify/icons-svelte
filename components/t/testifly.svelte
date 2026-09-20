<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca41jjffc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ca41jjffc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:testifly" {...props}></Icon>
