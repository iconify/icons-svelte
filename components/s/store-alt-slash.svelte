<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9xwewb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n9xwewb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:store-alt-slash" {...props}></Icon>
