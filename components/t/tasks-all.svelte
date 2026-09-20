<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_-22ibss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t_-22ibss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tasks-all" {...props}></Icon>
