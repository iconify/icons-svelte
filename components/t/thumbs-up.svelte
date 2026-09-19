<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d73ve3uwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d73ve3uwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:thumbs-up" {...props}></Icon>
