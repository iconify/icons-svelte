<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdnzapkwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdnzapkwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:syringe" {...props}></Icon>
