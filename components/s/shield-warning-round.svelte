<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdt7u2b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdt7u2b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-warning-round" {...props}></Icon>
