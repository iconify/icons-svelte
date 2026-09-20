<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfkqb6b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cfkqb6b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-rounded-rectangle-outline" {...props}></Icon>
