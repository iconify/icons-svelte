<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2pv8ibcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="o2pv8ibcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-f" {...props}></Icon>
