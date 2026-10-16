<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6t-wwj2r.css';
import '../../css/c/cm_9ngbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d6t-wwj2r"/><path class="cm_9ngbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semi-detached-20" {...props}></Icon>
