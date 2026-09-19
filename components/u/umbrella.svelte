<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtm7eswgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1600};
const content = `<path class="xtm7eswgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:umbrella" {...props}></Icon>
