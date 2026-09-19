<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6jk1mbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6jk1mbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scroll-quill" {...props}></Icon>
