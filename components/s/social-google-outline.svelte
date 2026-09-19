<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6o7nlbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6o7nlbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-google-outline" {...props}></Icon>
