<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_9sgybsj.css';
import '../../css/s/sd1bnsbfx.css';
import '../../css/t/teddm1b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s_9sgybsj"/><path class="sd1bnsbfx"/><path class="teddm1b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trowel-48-bold" {...props}></Icon>
