<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogz2-tlnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogz2-tlnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tornado" {...props}></Icon>
