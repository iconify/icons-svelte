<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk7y3tbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mk7y3tbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:th-large" {...props}></Icon>
