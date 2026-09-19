<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48r1da-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r48r1da-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:windows-alt" {...props}></Icon>
