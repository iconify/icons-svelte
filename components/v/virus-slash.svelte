<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o716c4d1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o716c4d1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:virus-slash" {...props}></Icon>
