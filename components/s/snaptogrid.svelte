<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s85dbh2lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s85dbh2lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:snaptogrid" {...props}></Icon>
