<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnpo3gbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnpo3gbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-missed-solid" {...props}></Icon>
