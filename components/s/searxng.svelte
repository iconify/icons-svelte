<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1bv8qxrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1bv8qxrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:searxng" {...props}></Icon>
