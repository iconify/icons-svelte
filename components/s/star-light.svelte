<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1y9ezhsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1y9ezhsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:star-light" {...props}></Icon>
