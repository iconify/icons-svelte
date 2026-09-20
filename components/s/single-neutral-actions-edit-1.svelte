<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6mpyj1vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6mpyj1vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-neutral-actions-edit-1" {...props}></Icon>
