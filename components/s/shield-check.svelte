<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a99lfebmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a99lfebmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-check" {...props}></Icon>
