<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krssq8osx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="krssq8osx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:view-tile" {...props}></Icon>
