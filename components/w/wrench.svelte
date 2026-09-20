<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1np-_ozh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x1np-_ozh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:wrench" {...props}></Icon>
