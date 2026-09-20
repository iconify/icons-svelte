<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h812qk4ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h812qk4ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wand-off" {...props}></Icon>
