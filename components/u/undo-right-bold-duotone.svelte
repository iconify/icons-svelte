<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp69ui1wu.css';
import '../../css/f/f63v77q_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wp69ui1wu"/><path class="f63v77q_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-bold-duotone" {...props}></Icon>
