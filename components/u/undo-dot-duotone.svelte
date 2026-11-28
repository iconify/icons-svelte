<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8kbf-b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v8kbf-b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:undo-dot-duotone" {...props}></Icon>
