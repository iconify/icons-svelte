<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he1_2w54z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":896};
const content = `<path class="he1_2w54z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zelda" {...props}></Icon>
