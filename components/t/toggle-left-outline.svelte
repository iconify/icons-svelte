<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nakc4kdbz.css';
import '../../css/w/wglt58box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nakc4kdbz"/><path class="wglt58box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:toggle-left-outline" {...props}></Icon>
