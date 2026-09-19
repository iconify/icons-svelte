<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr5v5lb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr5v5lb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:terminal-square" {...props}></Icon>
