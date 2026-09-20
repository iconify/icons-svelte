<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9h-btb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9h-btb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:verified-16" {...props}></Icon>
