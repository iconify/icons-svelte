<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duc9dub9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="duc9dub9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:video-conference" {...props}></Icon>
