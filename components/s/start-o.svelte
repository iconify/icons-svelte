<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaa3j5mot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="eaa3j5mot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:start-o" {...props}></Icon>
