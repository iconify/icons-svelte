<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5boo5bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5boo5bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zzz" {...props}></Icon>
