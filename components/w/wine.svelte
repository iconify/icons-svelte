<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-gel7b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="p-gel7b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wine" {...props}></Icon>
