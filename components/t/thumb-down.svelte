<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ookz8by-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ookz8by-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:thumb-down" {...props}></Icon>
