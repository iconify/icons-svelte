<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7-64xb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-64xb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-circle-light" {...props}></Icon>
