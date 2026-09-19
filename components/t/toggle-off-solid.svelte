<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8wqzpgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fz8wqzpgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:toggle-off-solid" {...props}></Icon>
