<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2_xfybja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n2_xfybja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-instagram" {...props}></Icon>
