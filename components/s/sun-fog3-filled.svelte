<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywkte3b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywkte3b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sun-fog3-filled" {...props}></Icon>
