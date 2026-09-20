<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ghuzbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ghuzbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tea" {...props}></Icon>
