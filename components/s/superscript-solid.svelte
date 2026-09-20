<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-u_94fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="x1-u_94fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:superscript-solid" {...props}></Icon>
