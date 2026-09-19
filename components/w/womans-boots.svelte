<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rravu28bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rravu28bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:womans-boots" {...props}></Icon>
