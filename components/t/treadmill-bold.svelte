<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6gx6-b_c.css';
import '../../css/u/ue3-gzbke.css';
import '../../css/y/yus7ucc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6gx6-b_c"/><path clip-rule="evenodd" class="ue3-gzbke"/><path class="yus7ucc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:treadmill-bold" {...props}></Icon>
