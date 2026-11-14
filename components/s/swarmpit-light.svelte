<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbt5dq_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbt5dq_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swarmpit-light" {...props}></Icon>
