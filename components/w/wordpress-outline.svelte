<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8svl7bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r8svl7bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wordpress-outline" {...props}></Icon>
