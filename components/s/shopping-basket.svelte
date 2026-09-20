<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uml9d-m-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="uml9d-m-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:shopping-basket" {...props}></Icon>
