<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl_1mshxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl_1mshxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:shield" {...props}></Icon>
