<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekdixv9xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekdixv9xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-4-line" {...props}></Icon>
