<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr_wuucje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr_wuucje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:ruler-combined" {...props}></Icon>
