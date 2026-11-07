<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw0niobhd.css';
import '../../css/i/iltuah3xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw0niobhd"/><path class="iltuah3xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-forward-bold" {...props}></Icon>
