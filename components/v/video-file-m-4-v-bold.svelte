<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l93-z5byc.css';
import '../../css/t/tc4axubag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l93-z5byc"/><path class="tc4axubag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-file-m-4-v-bold" {...props}></Icon>
