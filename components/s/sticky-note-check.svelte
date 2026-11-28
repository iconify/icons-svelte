<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh5dizfkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh5dizfkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sticky-note-check" {...props}></Icon>
