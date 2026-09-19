<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0kie0bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j0kie0bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:untappd" {...props}></Icon>
