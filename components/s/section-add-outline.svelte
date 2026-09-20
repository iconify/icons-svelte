<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouc5jvb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ouc5jvb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:section-add-outline" {...props}></Icon>
