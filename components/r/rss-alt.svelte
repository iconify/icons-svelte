<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6z0tzbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6z0tzbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rss-alt" {...props}></Icon>
