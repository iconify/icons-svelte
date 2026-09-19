<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcnk7q1qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcnk7q1qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sbs-chill" {...props}></Icon>
