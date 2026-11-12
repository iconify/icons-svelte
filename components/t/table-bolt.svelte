<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc1j5bc2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc1j5bc2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-bolt" {...props}></Icon>
