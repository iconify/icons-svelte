<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whft5_bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="whft5_bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tumblr" {...props}></Icon>
