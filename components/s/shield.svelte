<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq50l0kdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="wq50l0kdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield" {...props}></Icon>
