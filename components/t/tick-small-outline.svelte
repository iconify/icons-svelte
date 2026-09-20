<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dls6cz9sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dls6cz9sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tick-small-outline" {...props}></Icon>
