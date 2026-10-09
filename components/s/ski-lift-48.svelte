<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f54a80bxs.css';
import '../../css/h/hg9w13bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f54a80bxs"/><path class="hg9w13bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ski-lift-48" {...props}></Icon>
