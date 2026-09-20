<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byp3dbcaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="byp3dbcaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-reddit" {...props}></Icon>
