<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnb5tybzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnb5tybzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star-x" {...props}></Icon>
