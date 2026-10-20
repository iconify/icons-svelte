<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duw237w5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="duw237w5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:space-bar-20" {...props}></Icon>
