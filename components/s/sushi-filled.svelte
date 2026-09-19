<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unkwe7bpp.css';
import '../../css/u/uqzyn-kgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unkwe7bpp"/><path class="uqzyn-kgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sushi-filled" {...props}></Icon>
