<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na9r72qao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="na9r72qao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:travel-case" {...props}></Icon>
