<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-27md8lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="g-27md8lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:tennis-11" {...props}></Icon>
