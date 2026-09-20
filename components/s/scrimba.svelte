<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aker38-pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aker38-pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scrimba" {...props}></Icon>
