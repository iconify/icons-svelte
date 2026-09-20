<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neohn4bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neohn4bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:volume-control-up-1" {...props}></Icon>
