<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii0e4j_mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ii0e4j_mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:satellite-antenna" {...props}></Icon>
