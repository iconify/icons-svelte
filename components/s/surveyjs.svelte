<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4kqh8bxz.css';
import '../../css/e/ep6tlrbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4kqh8bxz"/><path class="ep6tlrbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surveyjs" {...props}></Icon>
