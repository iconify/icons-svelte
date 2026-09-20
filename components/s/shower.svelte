<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdu0okbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gdu0okbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shower" {...props}></Icon>
