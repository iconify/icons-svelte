<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_cuacnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my_cuacnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-left" {...props}></Icon>
