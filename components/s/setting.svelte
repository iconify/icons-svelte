<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv68w0biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv68w0biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:setting" {...props}></Icon>
