<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffcdkmbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffcdkmbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-wordpress-outline" {...props}></Icon>
