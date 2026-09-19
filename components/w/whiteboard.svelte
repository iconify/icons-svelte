<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je7ygt42x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je7ygt42x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:whiteboard" {...props}></Icon>
