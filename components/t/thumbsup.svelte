<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isjsz3ejb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isjsz3ejb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:thumbsup" {...props}></Icon>
