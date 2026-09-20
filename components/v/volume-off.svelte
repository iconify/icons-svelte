<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlqo4qu-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlqo4qu-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:volume-off" {...props}></Icon>
