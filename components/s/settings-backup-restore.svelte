<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmy94ub0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmy94ub0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-backup-restore" {...props}></Icon>
