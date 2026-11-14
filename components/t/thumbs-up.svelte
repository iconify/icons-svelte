<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgzzj0u0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgzzj0u0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:thumbs-up" {...props}></Icon>
