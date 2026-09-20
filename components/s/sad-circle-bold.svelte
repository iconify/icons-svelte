<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn3o-27jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nn3o-27jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sad-circle-bold" {...props}></Icon>
