<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hknn8vb1a.css';
import '../../css/k/ko05ptbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hknn8vb1a"/><path class="ko05ptbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:windows" {...props}></Icon>
