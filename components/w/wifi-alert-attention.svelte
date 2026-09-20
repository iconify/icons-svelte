<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fan5bvbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fan5bvbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-alert-attention" {...props}></Icon>
