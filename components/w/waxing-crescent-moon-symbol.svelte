<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rew5u3t-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rew5u3t-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:waxing-crescent-moon-symbol" {...props}></Icon>
