<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhk6x7b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nhk6x7b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:slash-20-solid" {...props}></Icon>
