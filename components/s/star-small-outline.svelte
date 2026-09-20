<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6fabdwkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g6fabdwkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:star-small-outline" {...props}></Icon>
