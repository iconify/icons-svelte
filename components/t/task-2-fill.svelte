<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abjtwonte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abjtwonte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:task-2-fill" {...props}></Icon>
