<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0uqsra_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0uqsra_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:sunflower" {...props}></Icon>
