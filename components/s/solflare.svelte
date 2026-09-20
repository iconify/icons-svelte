<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5s673s8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5s673s8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:solflare" {...props}></Icon>
