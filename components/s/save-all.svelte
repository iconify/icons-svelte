<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8ye8b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tj8ye8b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:save-all" {...props}></Icon>
