<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oftl5vb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oftl5vb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:system" {...props}></Icon>
