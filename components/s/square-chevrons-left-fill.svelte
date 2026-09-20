<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecto0z3-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecto0z3-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-left-fill" {...props}></Icon>
