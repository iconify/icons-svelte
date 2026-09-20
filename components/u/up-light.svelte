<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6usx4t3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6usx4t3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:up-light" {...props}></Icon>
