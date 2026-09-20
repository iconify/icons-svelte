<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh3iqkbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh3iqkbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:upload" {...props}></Icon>
