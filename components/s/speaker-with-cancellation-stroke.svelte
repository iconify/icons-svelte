<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdkvpfbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rdkvpfbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speaker-with-cancellation-stroke" {...props}></Icon>
