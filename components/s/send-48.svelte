<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtk7136by.css';
import '../../css/i/i3cagyb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qtk7136by"/><path class="i3cagyb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-48" {...props}></Icon>
