<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ulnzfce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ulnzfce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-up-alt-2-fill" {...props}></Icon>
