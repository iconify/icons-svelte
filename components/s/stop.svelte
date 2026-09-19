<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4f7-wb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h4f7-wb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:stop" {...props}></Icon>
