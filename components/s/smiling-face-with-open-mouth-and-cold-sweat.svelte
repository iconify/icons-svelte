<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3dpg2-tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g3dpg2-tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smiling-face-with-open-mouth-and-cold-sweat" {...props}></Icon>
