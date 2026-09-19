<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sukewzbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":614};
const content = `<path class="sukewzbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:video" {...props}></Icon>
