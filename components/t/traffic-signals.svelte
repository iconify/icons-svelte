<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9lkkjbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9lkkjbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:traffic-signals" {...props}></Icon>
