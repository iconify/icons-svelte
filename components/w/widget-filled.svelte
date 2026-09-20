<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeyo1tnaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="eeyo1tnaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:widget-filled" {...props}></Icon>
