<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_bfsh-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_bfsh-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-strikethrough" {...props}></Icon>
