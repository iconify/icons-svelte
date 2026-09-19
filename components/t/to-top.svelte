<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in5ftwbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="in5ftwbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:to-top" {...props}></Icon>
