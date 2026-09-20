<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8quy38i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it8quy38i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-shared-2-line" {...props}></Icon>
