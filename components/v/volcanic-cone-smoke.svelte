<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awckl0dec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awckl0dec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:volcanic-cone-smoke" {...props}></Icon>
