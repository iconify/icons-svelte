<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7o9e3bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="v7o9e3bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tablet-solid" {...props}></Icon>
