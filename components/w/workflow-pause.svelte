<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsapof_8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsapof_8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:workflow-pause" {...props}></Icon>
