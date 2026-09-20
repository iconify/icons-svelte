<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmsumsuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgmsumsuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:text-direction-l" {...props}></Icon>
