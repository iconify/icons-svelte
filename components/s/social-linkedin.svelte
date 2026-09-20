<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqkh30bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqkh30bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-linkedin" {...props}></Icon>
