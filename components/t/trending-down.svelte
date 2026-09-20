<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfaqad7fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfaqad7fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:trending-down" {...props}></Icon>
