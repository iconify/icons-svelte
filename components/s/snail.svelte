<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqlf2cjio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kqlf2cjio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:snail" {...props}></Icon>
