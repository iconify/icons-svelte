<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzp-x3bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzp-x3bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:shield-outline" {...props}></Icon>
