<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uko2ix2oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uko2ix2oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:veed" {...props}></Icon>
