<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycp1-7btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycp1-7btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:washing-machine-round" {...props}></Icon>
