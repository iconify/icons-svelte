<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvnguia1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fvnguia1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarecomment" {...props}></Icon>
