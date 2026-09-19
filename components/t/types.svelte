<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um2e2-7hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um2e2-7hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:types" {...props}></Icon>
