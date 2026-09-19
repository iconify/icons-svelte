<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs6y6ggvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fs6y6ggvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:xsplit" {...props}></Icon>
