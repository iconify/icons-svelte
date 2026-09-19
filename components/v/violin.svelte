<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqg-62b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gqg-62b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:violin" {...props}></Icon>
