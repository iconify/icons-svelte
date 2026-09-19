<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cedp-nw9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cedp-nw9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-down-filled" {...props}></Icon>
