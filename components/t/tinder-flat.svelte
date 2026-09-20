<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocmygckok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ocmygckok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:tinder-flat" {...props}></Icon>
