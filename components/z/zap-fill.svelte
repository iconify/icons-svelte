<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chax8xlzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chax8xlzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:zap-fill" {...props}></Icon>
