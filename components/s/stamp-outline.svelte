<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htane7bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="htane7bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stamp-outline" {...props}></Icon>
