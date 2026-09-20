<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg1wvhb_r.css';
import '../../css/j/j-6v1gb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jg1wvhb_r"/><path class="j-6v1gb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:taxi" {...props}></Icon>
