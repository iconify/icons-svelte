<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7oixqbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x7oixqbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:volume-mute" {...props}></Icon>
