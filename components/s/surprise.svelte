<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm_2ikbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="mm_2ikbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:surprise" {...props}></Icon>
