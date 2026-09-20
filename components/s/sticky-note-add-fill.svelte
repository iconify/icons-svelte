<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urbubkvgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urbubkvgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sticky-note-add-fill" {...props}></Icon>
