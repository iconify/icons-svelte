<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cak2t0brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cak2t0brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-solid" {...props}></Icon>
