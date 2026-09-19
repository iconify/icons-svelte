<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez88bsbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ez88bsbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tictactoe" {...props}></Icon>
