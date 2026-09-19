<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdqxufbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":39,"height":26};
const content = `<path class="pdqxufbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-capital-the-26" {...props}></Icon>
