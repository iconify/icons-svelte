<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7nc4kadu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7nc4kadu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:stairs-down-person" {...props}></Icon>
