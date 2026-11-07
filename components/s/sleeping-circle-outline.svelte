<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prq9nybvi.css';
import '../../css/a/aljlp2--c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prq9nybvi"/><path clip-rule="evenodd" class="aljlp2--c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sleeping-circle-outline" {...props}></Icon>
