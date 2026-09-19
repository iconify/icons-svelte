<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6jk8epgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s6jk8epgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:squarespace" {...props}></Icon>
