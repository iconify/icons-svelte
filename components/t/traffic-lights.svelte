<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an__cwb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="an__cwb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:traffic-lights" {...props}></Icon>
