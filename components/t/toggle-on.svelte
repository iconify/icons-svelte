<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m7n-bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7m7n-bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:toggle-on" {...props}></Icon>
