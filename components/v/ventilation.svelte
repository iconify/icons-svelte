<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faz80ofhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="faz80ofhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ventilation" {...props}></Icon>
