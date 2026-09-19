<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s73i_9bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s73i_9bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:unicode" {...props}></Icon>
