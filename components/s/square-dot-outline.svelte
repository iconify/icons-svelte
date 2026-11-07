<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er9_2_bjd.css';
import '../../css/n/n8eavcbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er9_2_bjd"/><path clip-rule="evenodd" class="n8eavcbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-dot-outline" {...props}></Icon>
