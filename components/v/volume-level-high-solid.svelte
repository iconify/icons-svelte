<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnw29gb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gnw29gb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-level-high-solid" {...props}></Icon>
