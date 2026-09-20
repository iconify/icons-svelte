<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg0wxebyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mg0wxebyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:suspension-railway" {...props}></Icon>
