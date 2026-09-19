<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqe44ubtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqe44ubtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:web-window-solid" {...props}></Icon>
