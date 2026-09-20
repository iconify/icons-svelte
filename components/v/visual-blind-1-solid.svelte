<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh5qm9e6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gh5qm9e6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:visual-blind-1-solid" {...props}></Icon>
