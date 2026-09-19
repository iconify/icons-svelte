<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im6fgsjxz.css';
import '../../css/x/xwibx1gek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im6fgsjxz"/><path class="xwibx1gek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:widget-small" {...props}></Icon>
