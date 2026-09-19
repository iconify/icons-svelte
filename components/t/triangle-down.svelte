<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj0kccuzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cj0kccuzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-down" {...props}></Icon>
