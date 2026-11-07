<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prq9nybvi.css';
import '../../css/q/qmmwrfbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prq9nybvi"/><path clip-rule="evenodd" class="qmmwrfbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sleeping-square-outline" {...props}></Icon>
