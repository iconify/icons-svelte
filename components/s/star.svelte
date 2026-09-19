<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji6w31kzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji6w31kzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:star" {...props}></Icon>
