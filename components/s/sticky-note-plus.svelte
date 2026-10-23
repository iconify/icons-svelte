<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd_920bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_920bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sticky-note-plus" {...props}></Icon>
