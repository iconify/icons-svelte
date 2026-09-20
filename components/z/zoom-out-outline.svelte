<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys_em6wiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys_em6wiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:zoom-out-outline" {...props}></Icon>
