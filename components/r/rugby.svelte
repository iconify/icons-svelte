<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do_kecb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do_kecb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rugby" {...props}></Icon>
