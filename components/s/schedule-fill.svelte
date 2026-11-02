<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgu22vc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgu22vc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:schedule-fill" {...props}></Icon>
