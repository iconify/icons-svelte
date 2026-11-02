<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh70a0b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh70a0b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-1-line" {...props}></Icon>
