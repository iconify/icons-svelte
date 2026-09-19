<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq15az8iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq15az8iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-instagram-outline" {...props}></Icon>
