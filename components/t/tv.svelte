<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag6ih3byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ag6ih3byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tv" {...props}></Icon>
