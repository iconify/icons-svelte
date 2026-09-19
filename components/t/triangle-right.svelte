<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s19bvnbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s19bvnbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-right" {...props}></Icon>
