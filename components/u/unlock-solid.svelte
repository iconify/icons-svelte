<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrn2ykbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrn2ykbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:unlock-solid" {...props}></Icon>
