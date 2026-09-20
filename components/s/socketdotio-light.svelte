<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1--m9kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gr1--m9kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:socketdotio-light" {...props}></Icon>
