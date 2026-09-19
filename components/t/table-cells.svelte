<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8tswj24l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s8tswj24l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:table-cells" {...props}></Icon>
