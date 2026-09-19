<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2dmbzbpi.css';
import '../../css/l/l1v0zsvht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2dmbzbpi"/><path class="l1v0zsvht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:speaker-filled" {...props}></Icon>
