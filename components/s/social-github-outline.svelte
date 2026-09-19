<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdr_w8b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdr_w8b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-github-outline" {...props}></Icon>
