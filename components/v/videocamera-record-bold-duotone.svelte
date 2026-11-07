<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a10be2bti.css';
import '../../css/t/tpknrjtqz.css';
import '../../css/e/e_jwy8bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a10be2bti"/><path class="tpknrjtqz"/><path clip-rule="evenodd" class="e_jwy8bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-record-bold-duotone" {...props}></Icon>
