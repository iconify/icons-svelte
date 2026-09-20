<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmbla7-hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmbla7-hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sun-rising" {...props}></Icon>
