<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5-7hbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="id5-7hbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:s-upper-case" {...props}></Icon>
