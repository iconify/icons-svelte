<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3jv3vjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qs3jv3vjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:turn-sign-bold" {...props}></Icon>
