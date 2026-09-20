<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndsum8b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndsum8b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:volleyball-net-bold" {...props}></Icon>
