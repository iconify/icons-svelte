<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2prm9rra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h2prm9rra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:share-alt" {...props}></Icon>
