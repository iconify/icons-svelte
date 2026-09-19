<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_plebwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj_plebwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:stark" {...props}></Icon>
