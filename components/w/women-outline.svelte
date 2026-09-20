<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chw7yu-vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="chw7yu-vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:women-outline" {...props}></Icon>
