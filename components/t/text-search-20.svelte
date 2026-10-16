<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmqzfdcfq.css';
import '../../css/m/mq74mlbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmqzfdcfq"/><path class="mq74mlbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-search-20" {...props}></Icon>
