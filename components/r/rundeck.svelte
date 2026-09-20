<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7jh_uzap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7jh_uzap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rundeck" {...props}></Icon>
