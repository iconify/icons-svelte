<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpe2vkb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xpe2vkb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:skip-forward" {...props}></Icon>
