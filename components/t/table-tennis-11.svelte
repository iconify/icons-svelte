<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvdhh0tlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vvdhh0tlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:table-tennis-11" {...props}></Icon>
