<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le8sjw5jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="le8sjw5jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:stopwatch-filled" {...props}></Icon>
