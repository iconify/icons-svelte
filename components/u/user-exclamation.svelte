<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc5znpb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc5znpb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-exclamation" {...props}></Icon>
