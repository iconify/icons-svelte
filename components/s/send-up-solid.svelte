<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1giy57js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j1giy57js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-up-solid" {...props}></Icon>
