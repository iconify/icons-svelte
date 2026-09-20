<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8oo8ds2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8oo8ds2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wattpad" {...props}></Icon>
