<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aipr_bcuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aipr_bcuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:spinner" {...props}></Icon>
