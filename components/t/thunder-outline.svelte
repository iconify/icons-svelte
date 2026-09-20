<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzz_njbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzz_njbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thunder-outline" {...props}></Icon>
