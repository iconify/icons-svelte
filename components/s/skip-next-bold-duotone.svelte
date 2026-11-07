<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr5sybb7w.css';
import '../../css/c/cdhe4sbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5sybb7w"/><path class="cdhe4sbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skip-next-bold-duotone" {...props}></Icon>
