<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8aqrybuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k8aqrybuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shape-unite" {...props}></Icon>
