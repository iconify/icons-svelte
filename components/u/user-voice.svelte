<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svetj300y.css';
import '../../css/g/gwn0owbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svetj300y"/><path class="gwn0owbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-voice" {...props}></Icon>
