<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udao9qkrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udao9qkrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:wrench" {...props}></Icon>
