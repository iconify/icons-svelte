<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf8klcbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf8klcbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:thumb-up-off" {...props}></Icon>
