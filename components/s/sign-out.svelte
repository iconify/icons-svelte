<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uodm3s_en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uodm3s_en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:sign-out" {...props}></Icon>
