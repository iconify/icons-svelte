<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs1lgy2sf.css';
import '../../css/f/ft-qacc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs1lgy2sf"/><path class="ft-qacc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:task-list-pin-bold" {...props}></Icon>
