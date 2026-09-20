<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l60g_u.css';
import '../../css/d/d-opowom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l60g_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:twitter-x-alt" {...props}></Icon>
