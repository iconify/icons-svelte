<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvygl72pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nvygl72pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smirking-face" {...props}></Icon>
