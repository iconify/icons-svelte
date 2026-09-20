<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gohqr0bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gohqr0bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:trophy" {...props}></Icon>
