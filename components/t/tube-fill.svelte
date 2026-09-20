<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy8j3sb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy8j3sb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tube-fill" {...props}></Icon>
