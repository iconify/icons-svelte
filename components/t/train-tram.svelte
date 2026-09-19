<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grc9q2ges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="grc9q2ges"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:train-tram" {...props}></Icon>
