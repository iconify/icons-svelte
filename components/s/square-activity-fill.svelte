<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd5122bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd5122bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-activity-fill" {...props}></Icon>
