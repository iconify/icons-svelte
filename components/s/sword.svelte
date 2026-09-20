<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d657q-ouo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d657q-ouo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sword" {...props}></Icon>
