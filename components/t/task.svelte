<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agtflua3y.css';
import '../../css/y/yahv79bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agtflua3y"/><path class="yahv79bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:task" {...props}></Icon>
