<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_f5fmb5w.css';
import '../../css/d/dgp7bubto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_f5fmb5w"/><path class="dgp7bubto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:window-restore-solid" {...props}></Icon>
