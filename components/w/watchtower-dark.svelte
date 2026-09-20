<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2q-obza.css';
import '../../css/s/s_1q0sbix.css';
import '../../css/w/w37xe3b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud2q-obza"/><path class="s_1q0sbix"/><path class="w37xe3b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchtower-dark" {...props}></Icon>
