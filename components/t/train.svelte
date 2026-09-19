<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umng054pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="umng054pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:train" {...props}></Icon>
