<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6g1oc4ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g6g1oc4ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:underline" {...props}></Icon>
