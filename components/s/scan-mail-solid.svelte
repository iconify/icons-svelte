<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-49hjbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-49hjbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-mail-solid" {...props}></Icon>
