<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htdwecomi.css';
import '../../css/a/a7pe4ku8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htdwecomi"/><path class="a7pe4ku8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:timer-filled" {...props}></Icon>
