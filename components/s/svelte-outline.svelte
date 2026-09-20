<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya00f5jao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ya00f5jao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:svelte-outline" {...props}></Icon>
