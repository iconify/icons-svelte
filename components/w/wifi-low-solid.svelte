<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3v5spfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm3v5spfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-low-solid" {...props}></Icon>
