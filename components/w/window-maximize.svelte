<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c39rs6ueb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c39rs6ueb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:window-maximize" {...props}></Icon>
