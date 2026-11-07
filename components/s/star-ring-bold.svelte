<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3c204bfu.css';
import '../../css/z/zxb9zmb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3c204bfu"/><path clip-rule="evenodd" class="zxb9zmb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-ring-bold" {...props}></Icon>
