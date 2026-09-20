<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj-ki2brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-ki2brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:steering-2-line" {...props}></Icon>
