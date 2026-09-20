<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgklwys6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pgklwys6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-small-outline" {...props}></Icon>
