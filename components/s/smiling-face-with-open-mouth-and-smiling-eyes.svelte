<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1mwht5bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p1mwht5bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smiling-face-with-open-mouth-and-smiling-eyes" {...props}></Icon>
