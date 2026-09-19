<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjkzw0bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="qjkzw0bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-basket-add" {...props}></Icon>
