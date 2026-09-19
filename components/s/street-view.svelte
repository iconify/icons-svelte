<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2j3a6bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e2j3a6bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:street-view" {...props}></Icon>
