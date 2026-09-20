<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmwrbob4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kmwrbob4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:umbrella" {...props}></Icon>
