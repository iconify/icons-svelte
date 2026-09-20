<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sydoq6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sydoq6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:showpad" {...props}></Icon>
