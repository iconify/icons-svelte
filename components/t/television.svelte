<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k57r_666u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k57r_666u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:television" {...props}></Icon>
