<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ofxbc0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y_ofxbc0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:staff-snake" {...props}></Icon>
