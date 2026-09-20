<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbzc4ebog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbzc4ebog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler4" {...props}></Icon>
