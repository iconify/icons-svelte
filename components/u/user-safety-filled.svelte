<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt0j3ybxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt0j3ybxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-safety-filled" {...props}></Icon>
