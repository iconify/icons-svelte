<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj9mas2wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj9mas2wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scissors" {...props}></Icon>
