<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5ari44h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un5ari44h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-edit-style" {...props}></Icon>
