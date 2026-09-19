<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osgzido7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="osgzido7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:umbrella" {...props}></Icon>
