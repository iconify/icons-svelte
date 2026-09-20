<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzjc2bc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzjc2bc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:smart-key-remix" {...props}></Icon>
