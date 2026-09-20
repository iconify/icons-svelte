<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilqr3leb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilqr3leb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:trending-up" {...props}></Icon>
