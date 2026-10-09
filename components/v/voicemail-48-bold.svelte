<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpgircbhz.css';
import '../../css/o/ouirlxbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gpgircbhz"/><path class="ouirlxbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voicemail-48-bold" {...props}></Icon>
