<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4m3u2mna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h4m3u2mna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:unindent" {...props}></Icon>
