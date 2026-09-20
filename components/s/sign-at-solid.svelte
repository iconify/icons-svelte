<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofw0-zwkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ofw0-zwkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sign-at-solid" {...props}></Icon>
