<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftxh2yu-e.css';
import '../../css/p/pinggybge.css';
import '../../css/e/e3jlgobxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftxh2yu-e"/><path class="pinggybge"/><path class="e3jlgobxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-right-bold-duotone" {...props}></Icon>
