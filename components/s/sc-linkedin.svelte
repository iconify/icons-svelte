<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvdvcxqfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hvdvcxqfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-linkedin" {...props}></Icon>
