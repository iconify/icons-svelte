<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ys20bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k8ys20bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tram-with-pantograph-on-tram-track" {...props}></Icon>
