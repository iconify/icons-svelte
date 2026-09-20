<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daypf_7io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="daypf_7io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shield-outline" {...props}></Icon>
