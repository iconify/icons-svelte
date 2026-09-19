<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/webnvt7xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="webnvt7xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:transgender" {...props}></Icon>
