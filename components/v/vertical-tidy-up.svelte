<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmksmhets.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmksmhets"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:vertical-tidy-up" {...props}></Icon>
