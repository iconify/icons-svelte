<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cju3cub3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cju3cub3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:undo-circle-solid" {...props}></Icon>
