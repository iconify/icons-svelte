<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip2eoqmfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ip2eoqmfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:swap-vertical" {...props}></Icon>
